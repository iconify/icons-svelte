<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1nhrjbem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g1nhrjbem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:html-five2" {...props}></Icon>
