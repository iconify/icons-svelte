<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c564wd2vb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c564wd2vb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bell-ring" {...props}></Icon>
