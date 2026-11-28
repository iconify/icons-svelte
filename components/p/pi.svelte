<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6th-8ofz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6th-8ofz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:pi" {...props}></Icon>
