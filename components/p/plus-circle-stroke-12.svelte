<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glcmzy-4i.css';
import '../../css/c/cx7tzdb4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<circle class="glcmzy-4i"/><path class="cx7tzdb4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:plus-circle-stroke-12" {...props}></Icon>
