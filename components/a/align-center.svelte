<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gplgdq1bf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gplgdq1bf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:align-center" {...props}></Icon>
