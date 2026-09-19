<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tav496pqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tav496pqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:lets-encrypt" {...props}></Icon>
