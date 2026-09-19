<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw9-g6b6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cw9-g6b6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:pivx" {...props}></Icon>
