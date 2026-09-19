<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfp95qq4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qfp95qq4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-down-c" {...props}></Icon>
