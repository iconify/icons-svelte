<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcvp2ac6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kcvp2ac6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:copy-check-fill" {...props}></Icon>
