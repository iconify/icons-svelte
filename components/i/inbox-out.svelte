<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md585jgiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="md585jgiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:inbox-out" {...props}></Icon>
