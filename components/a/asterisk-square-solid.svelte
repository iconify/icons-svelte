<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmk1owber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmk1owber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:asterisk-square-solid" {...props}></Icon>
