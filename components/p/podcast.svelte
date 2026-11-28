<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl7xp8btf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yl7xp8btf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:podcast" {...props}></Icon>
