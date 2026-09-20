<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n27emnbuv.css';
import '../../css/x/x_3uzco3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n27emnbuv"/><rect class="x_3uzco3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:markdoc" {...props}></Icon>
