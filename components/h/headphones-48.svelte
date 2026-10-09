<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf7rtccfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zf7rtccfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:headphones-48" {...props}></Icon>
