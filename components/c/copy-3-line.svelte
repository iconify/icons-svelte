<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l92x6sbqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l92x6sbqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:copy-3-line" {...props}></Icon>
