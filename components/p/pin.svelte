<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl9zzjscs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="jl9zzjscs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:pin" {...props}></Icon>
