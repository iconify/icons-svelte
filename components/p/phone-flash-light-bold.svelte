<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r41gwzhxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r41gwzhxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:phone-flash-light-bold" {...props}></Icon>
