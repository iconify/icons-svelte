<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aybjhpbqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aybjhpbqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrows-pointing-out-20-solid" {...props}></Icon>
