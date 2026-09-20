<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcghi8bhd.css';
import '../../css/a/a_yeysi6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wcghi8bhd"/><path class="a_yeysi6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:copy-paste-clipboard" {...props}></Icon>
