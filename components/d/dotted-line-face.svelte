<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0xbhesyu.css';
import '../../css/f/fouayebow.css';
import '../../css/s/soumptb5m.css';
import '../../css/w/wzd7dfbhf.css';
import '../../css/k/kef9-snwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="d0xbhesyu"/><circle class="fouayebow"/><circle class="soumptb5m"/><path class="wzd7dfbhf"/><path class="kef9-snwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:dotted-line-face" {...props}></Icon>
