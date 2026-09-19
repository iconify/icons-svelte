<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p20be8wjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="p20be8wjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:cloudscale" {...props}></Icon>
