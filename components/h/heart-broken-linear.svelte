<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv54xkpie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rv54xkpie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:heart-broken-linear" {...props}></Icon>
