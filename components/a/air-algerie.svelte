<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ortm4mvgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":175.748,"height":105.761};
const content = `<path clip-rule="evenodd" class="ortm4mvgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:air-algerie" {...props}></Icon>
