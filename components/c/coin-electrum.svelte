<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqx6hhwyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="sqx6hhwyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:coin-electrum" {...props}></Icon>
