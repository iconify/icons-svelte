<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9o8enrad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9o8enrad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:boxes" {...props}></Icon>
