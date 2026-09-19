<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml1d8i_dw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ml1d8i_dw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:external" {...props}></Icon>
