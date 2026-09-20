<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp7_1q3hr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yp7_1q3hr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-pull-request-close-line" {...props}></Icon>
