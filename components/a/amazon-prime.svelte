<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-la4bbbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":4605.7,"height":2723.6};
const content = `<path class="n-la4bbbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:amazon-prime" {...props}></Icon>
