<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by87w4spn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="by87w4spn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:folder-minus-solid" {...props}></Icon>
