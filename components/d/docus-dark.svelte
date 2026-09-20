<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3zypgb3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":33,"height":32};
const content = `<path clip-rule="evenodd" class="m3zypgb3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:docus-dark" {...props}></Icon>
