<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1tz2rciq.css';
import '../../css/t/t8vg6kras.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u1tz2rciq"/><path class="t8vg6kras"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:adobe-after-effects-logo-bold" {...props}></Icon>
