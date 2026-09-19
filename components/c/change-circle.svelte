<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjnu8mbcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gjnu8mbcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:change-circle" {...props}></Icon>
