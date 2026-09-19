<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6n_bjbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s6n_bjbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-line-smooth" {...props}></Icon>
