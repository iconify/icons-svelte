<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b84h5jsba.css';
import '../../css/l/l9-hh0blx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b84h5jsba"/><path class="l9-hh0blx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-engineering-systems-design-rhapsody-sn2" {...props}></Icon>
