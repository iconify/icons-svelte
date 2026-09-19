<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e__s27uzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e__s27uzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:album" {...props}></Icon>
