<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as7zp-tqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="as7zp-tqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-all" {...props}></Icon>
