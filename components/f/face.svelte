<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s27d_blek.css';
import '../../css/p/pjyeu65td.css';
import '../../css/h/hcj6o-bax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s27d_blek"/><circle class="pjyeu65td"/><circle class="hcj6o-bax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:face" {...props}></Icon>
