<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk_1fybkb.css';
import '../../css/h/hc5l59cwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lk_1fybkb"/><path class="hc5l59cwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:codespaces-24" {...props}></Icon>
