<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4u5icbnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4u5icbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:bookmark-minus-solid" {...props}></Icon>
