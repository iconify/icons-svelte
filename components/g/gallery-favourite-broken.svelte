<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f1xuy0btj.css';
import '../../css/s/sixfdvbze.css';
import '../../css/i/iucnxxyud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f1xuy0btj"/><path class="sixfdvbze"/><path class="iucnxxyud"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gallery-favourite-broken" {...props}></Icon>
