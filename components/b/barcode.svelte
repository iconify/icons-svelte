<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfn44r7ax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfn44r7ax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:barcode" {...props}></Icon>
