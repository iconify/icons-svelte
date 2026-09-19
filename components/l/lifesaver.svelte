<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3f1dnbre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n3f1dnbre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:lifesaver" {...props}></Icon>
