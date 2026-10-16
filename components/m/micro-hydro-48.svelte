<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mexbaph4c.css';
import '../../css/c/c89fhw9bu.css';
import '../../css/l/lm4-qnbeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mexbaph4c"/><path class="c89fhw9bu"/><path class="lm4-qnbeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:micro-hydro-48" {...props}></Icon>
