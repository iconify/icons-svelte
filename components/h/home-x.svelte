<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-5kho9ad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-5kho9ad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:home-x" {...props}></Icon>
