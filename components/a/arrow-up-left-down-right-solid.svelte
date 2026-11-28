<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3cw-ybsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3cw-ybsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-up-left-down-right-solid" {...props}></Icon>
