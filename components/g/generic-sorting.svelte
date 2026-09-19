<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf2wg-b4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pf2wg-b4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:generic-sorting" {...props}></Icon>
