<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7_b83bfo.css';
import '../../css/w/w6uz2sbpd.css';
import '../../css/e/epr-bjb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x7_b83bfo"/><circle class="w6uz2sbpd"/><path class="epr-bjb7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:logo-ionic" {...props}></Icon>
