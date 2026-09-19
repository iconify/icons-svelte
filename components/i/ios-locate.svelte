<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwlq_8b3i.css';
import '../../css/r/roy4gvbpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uwlq_8b3i"/><path class="roy4gvbpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-locate" {...props}></Icon>
