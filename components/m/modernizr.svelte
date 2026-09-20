<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv65n-s5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pv65n-s5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:modernizr" {...props}></Icon>
