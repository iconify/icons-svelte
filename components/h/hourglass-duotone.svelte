<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m2t8ukb8a.css';
import '../../css/m/m23bbfw8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m2t8ukb8a"/><path class="m23bbfw8i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:hourglass-duotone" {...props}></Icon>
