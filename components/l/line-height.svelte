<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xit4yh0_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xit4yh0_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:line-height" {...props}></Icon>
