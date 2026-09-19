<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exm6s8_rj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="exm6s8_rj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:codacy" {...props}></Icon>
