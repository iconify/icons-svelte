<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_nf9ib3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_nf9ib3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:align-left" {...props}></Icon>
