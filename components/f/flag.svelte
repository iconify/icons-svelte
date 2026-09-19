<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg_kyn8ep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gg_kyn8ep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:flag" {...props}></Icon>
