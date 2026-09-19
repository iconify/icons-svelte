<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phjh-5c_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="phjh-5c_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:character-sentence-case" {...props}></Icon>
