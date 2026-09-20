<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynxtips6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ynxtips6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:h" {...props}></Icon>
