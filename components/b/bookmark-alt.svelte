<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yftn1vhpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yftn1vhpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:bookmark-alt" {...props}></Icon>
