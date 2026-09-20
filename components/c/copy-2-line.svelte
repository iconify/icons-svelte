<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd32qka9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wd32qka9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:copy-2-line" {...props}></Icon>
