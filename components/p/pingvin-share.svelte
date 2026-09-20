<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/va62ij8gu.css';
import '../../css/t/t0cly4bsd.css';
import '../../css/c/cj1l5ubxv.css';
import '../../css/d/dgggh2b8d.css';
import '../../css/k/kauhh8s-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="va62ij8gu"/><path class="t0cly4bsd"/><path class="cj1l5ubxv"/><path class="dgggh2b8d"/><path class="kauhh8s-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pingvin-share" {...props}></Icon>
