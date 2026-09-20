<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ualv6vazw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ualv6vazw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:location-pin-alt" {...props}></Icon>
