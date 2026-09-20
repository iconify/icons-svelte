<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew1qhpbly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ew1qhpbly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:nodemon" {...props}></Icon>
