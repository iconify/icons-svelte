<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt8glibwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lt8glibwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:align-bottom" {...props}></Icon>
