<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5ytx1huk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="k5ytx1huk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:k3os" {...props}></Icon>
