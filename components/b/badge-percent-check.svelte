<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6s8su6gi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6s8su6gi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:badge-percent-check" {...props}></Icon>
