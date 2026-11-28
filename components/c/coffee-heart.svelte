<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmg5gpb5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmg5gpb5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:coffee-heart" {...props}></Icon>
