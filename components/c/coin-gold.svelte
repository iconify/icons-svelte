<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nof6d3bsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="nof6d3bsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:coin-gold" {...props}></Icon>
