<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/i/iua0b4tie.css';
import '../../css/d/dndy5ccgm.css';
import '../../css/q/q1uumkb4y.css';
import '../../css/r/rcyotpv1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="iua0b4tie wm-shadow"/><path class="dndy5ccgm wm-shadow"/><path class="q1uumkb4y"/><path class="rcyotpv1e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:airplay" {...props}></Icon>
