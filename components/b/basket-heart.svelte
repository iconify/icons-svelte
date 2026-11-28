<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isj2kzbat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="isj2kzbat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:basket-heart" {...props}></Icon>
