<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djn_kwbxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="djn_kwbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:recording-sharp" {...props}></Icon>
