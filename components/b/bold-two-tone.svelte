<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko1__nbwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ko1__nbwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bold-two-tone" {...props}></Icon>
