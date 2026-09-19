<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oljjdabgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="oljjdabgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:box" {...props}></Icon>
