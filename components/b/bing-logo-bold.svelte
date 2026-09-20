<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt1ztnb6x.css';
import '../../css/l/ldryaf89d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dt1ztnb6x"/><path class="ldryaf89d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:bing-logo-bold" {...props}></Icon>
