<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtfp4lbkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qtfp4lbkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:envato" {...props}></Icon>
