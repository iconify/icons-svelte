<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aev0f0bxv.css';
import '../../css/b/b-yzc2u7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="aev0f0bxv"/><path class="b-yzc2u7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:archive" {...props}></Icon>
