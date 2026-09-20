<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4g6f4bfq.css';
import '../../css/m/ml0gmablf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n4g6f4bfq"/><path class="ml0gmablf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:cuda" {...props}></Icon>
