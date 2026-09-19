<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9cdyobop.css';
import '../../css/g/gzydm7bdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v9cdyobop"/><path class="gzydm7bdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:angle" {...props}></Icon>
