<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/geqzp7bnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="geqzp7bnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:ok" {...props}></Icon>
