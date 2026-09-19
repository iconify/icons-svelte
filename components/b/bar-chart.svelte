<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9v9lzovw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t9v9lzovw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:bar-chart" {...props}></Icon>
