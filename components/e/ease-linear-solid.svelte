<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx1xvfbqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xx1xvfbqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ease-linear-solid" {...props}></Icon>
