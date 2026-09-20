<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hg7duf-dx.css';
import '../../css/j/j1uuoibsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hg7duf-dx"/><path class="j1uuoibsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dot-grid-line" {...props}></Icon>
