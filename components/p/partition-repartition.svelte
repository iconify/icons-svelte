<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1dhfvbmz.css';
import '../../css/c/cymo4yqyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k1dhfvbmz"/><path class="cymo4yqyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:partition-repartition" {...props}></Icon>
