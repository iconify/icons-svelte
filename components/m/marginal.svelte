<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv5v4ubor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kv5v4ubor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:marginal" {...props}></Icon>
