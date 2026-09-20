<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqaaombks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="gqaaombks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:clarity" {...props}></Icon>
