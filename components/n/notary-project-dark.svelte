<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gm68y3b7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":800,"height":800};
const content = `<path class="gm68y3b7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:notary-project-dark" {...props}></Icon>
