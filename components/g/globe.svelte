<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek4thtbna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ek4thtbna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:globe" {...props}></Icon>
