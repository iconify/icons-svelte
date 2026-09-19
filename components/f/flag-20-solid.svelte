<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du0febchq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="du0febchq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:flag-20-solid" {...props}></Icon>
