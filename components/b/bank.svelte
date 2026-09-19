<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2ibkr3co.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2ibkr3co"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:bank" {...props}></Icon>
