<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0_tdbckx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":25,"left":4};
const content = `<path class="w0_tdbckx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:radix-ui-dark" {...props}></Icon>
