<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj0wbccem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hj0wbccem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:flag-finish-check" {...props}></Icon>
