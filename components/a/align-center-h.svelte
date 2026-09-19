<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg-xv732t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wg-xv732t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:align-center-h" {...props}></Icon>
