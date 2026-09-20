<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3kuv-btg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="g3kuv-btg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:appveyor" {...props}></Icon>
