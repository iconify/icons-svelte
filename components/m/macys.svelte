<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbiehttez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cbiehttez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:macys" {...props}></Icon>
