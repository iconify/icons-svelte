<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ch76cibil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="ch76cibil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:police-11" {...props}></Icon>
