<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uorsw2bdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="uorsw2bdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:reactnavigation" {...props}></Icon>
