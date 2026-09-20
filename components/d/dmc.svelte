<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u61vl1b-h.css';
import '../../css/u/ud94oijxq.css';
import '../../css/h/h2dcacdji.css';
import '../../css/s/s_hyqiben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u61vl1b-h"/><path class="ud94oijxq"/><path class="h2dcacdji"/><path class="s_hyqiben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:dmc" {...props}></Icon>
