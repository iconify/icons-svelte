<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw_globds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pw_globds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:kidneys-outline-24px" {...props}></Icon>
