<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1qa-m9-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m1qa-m9-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:hpp" {...props}></Icon>
