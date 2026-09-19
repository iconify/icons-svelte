<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkmf2zbrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kkmf2zbrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:ary" {...props}></Icon>
