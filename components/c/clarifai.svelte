<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chr3v_s-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chr3v_s-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:clarifai" {...props}></Icon>
