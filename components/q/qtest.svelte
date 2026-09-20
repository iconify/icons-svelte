<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqtu27v6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="vqtu27v6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:qtest" {...props}></Icon>
