<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa3-w-bbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fa3-w-bbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:code-variable" {...props}></Icon>
