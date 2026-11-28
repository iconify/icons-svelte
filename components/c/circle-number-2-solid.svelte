<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtrcekbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rtrcekbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-number-2-solid" {...props}></Icon>
