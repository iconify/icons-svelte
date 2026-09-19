<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gd0l9kb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":24};
const content = `<path class="gd0l9kb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:android" {...props}></Icon>
