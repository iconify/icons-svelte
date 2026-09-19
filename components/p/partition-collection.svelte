<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lde4pncda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lde4pncda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:partition-collection" {...props}></Icon>
