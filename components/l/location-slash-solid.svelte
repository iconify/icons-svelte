<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4x23oj2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4x23oj2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:location-slash-solid" {...props}></Icon>
