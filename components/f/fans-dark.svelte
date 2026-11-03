<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2delqbxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="d2delqbxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fans-dark" {...props}></Icon>
