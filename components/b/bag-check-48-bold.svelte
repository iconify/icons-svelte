<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqivvfbyi.css';
import '../../css/z/z6525nbnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="aqivvfbyi"/><path class="z6525nbnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bag-check-48-bold" {...props}></Icon>
