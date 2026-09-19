<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qiuiq63rg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qiuiq63rg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:arrows-left-right" {...props}></Icon>
