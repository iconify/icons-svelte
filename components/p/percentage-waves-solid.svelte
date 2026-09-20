<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dir0ivzqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dir0ivzqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:percentage-waves-solid" {...props}></Icon>
