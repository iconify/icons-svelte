<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/l/ldq1rs.css';
import '../../css/k/kpnc8p.css';
import '../../css/l/l5mhfr.css';
import '../../css/s/so-from-20.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c ldq1rs"/><path class="a0m25c kpnc8p"/><path class="a0m25c l5mhfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:arrow-open-left" {...props}></Icon>
