<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytjvhenfl.css';
import '../../css/d/df6t0qb7f.css';
import '../../css/m/mgt7vwb6i.css';
import '../../css/q/qawukvmtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytjvhenfl"/><path clip-rule="evenodd" class="df6t0qb7f"/><path clip-rule="evenodd" class="mgt7vwb6i"/><path clip-rule="evenodd" class="qawukvmtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cart-check-outline" {...props}></Icon>
