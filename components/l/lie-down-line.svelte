<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfwe9dsqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfwe9dsqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lie-down-line" {...props}></Icon>
