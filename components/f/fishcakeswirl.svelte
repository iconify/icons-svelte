<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny2sfabep.css';
import '../../css/n/nnbs2674t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ny2sfabep"/><path class="nnbs2674t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:fishcakeswirl" {...props}></Icon>
