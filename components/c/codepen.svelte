<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5a7bnb_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5a7bnb_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:codepen" {...props}></Icon>
