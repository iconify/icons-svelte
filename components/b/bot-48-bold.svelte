<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu1885bds.css';
import '../../css/x/x3viw0xpi.css';
import '../../css/z/zn1bmf10z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qu1885bds"/><path class="x3viw0xpi"/><path class="zn1bmf10z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bot-48-bold" {...props}></Icon>
