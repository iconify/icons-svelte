<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/augzmwl8c.css';
import '../../css/r/rc0brcrfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="augzmwl8c"/><path class="rc0brcrfr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:credit-card-detailed-duotone" {...props}></Icon>
