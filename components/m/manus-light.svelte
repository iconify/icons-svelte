<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pglcr0mfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":60,"height":60};
const content = `<path clip-rule="evenodd" class="pglcr0mfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:manus-light" {...props}></Icon>
