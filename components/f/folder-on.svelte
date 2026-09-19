<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb8mnr2cq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cb8mnr2cq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:folder-on" {...props}></Icon>
