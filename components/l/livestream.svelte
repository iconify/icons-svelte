<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2hylacvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<path class="x2hylacvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:livestream" {...props}></Icon>
