<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enj9kbcag.css';
import '../../css/l/ls7lhjm1d.css';
import '../../css/q/qi4h0bbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="enj9kbcag"/><path class="ls7lhjm1d"/><path class="qi4h0bbag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:power-cable-20-bold" {...props}></Icon>
