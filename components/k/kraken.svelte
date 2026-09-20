<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv0oiobzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hv0oiobzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:kraken" {...props}></Icon>
