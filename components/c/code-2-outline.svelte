<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t519rybsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t519rybsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:code-2-outline" {...props}></Icon>
