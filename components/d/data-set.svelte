<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oph9_fobs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oph9_fobs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-set" {...props}></Icon>
