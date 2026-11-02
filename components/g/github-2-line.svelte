<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqsvi1ncw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqsvi1ncw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:github-2-line" {...props}></Icon>
