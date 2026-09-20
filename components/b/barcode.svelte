<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtpvajg4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtpvajg4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:barcode" {...props}></Icon>
