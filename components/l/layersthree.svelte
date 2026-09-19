<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkx1agbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qkx1agbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:layersthree" {...props}></Icon>
