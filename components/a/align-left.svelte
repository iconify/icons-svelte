<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f08tylbcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f08tylbcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:align-left" {...props}></Icon>
