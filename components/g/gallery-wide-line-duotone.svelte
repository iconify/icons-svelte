<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/euo2u3bkq.css';
import '../../css/k/k66tt2kvs.css';
import '../../css/a/avzbbbb-w.css';
import '../../css/e/enjp2ob5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="euo2u3bkq"/><path class="k66tt2kvs"/><path class="avzbbbb-w"/><circle class="enjp2ob5n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gallery-wide-line-duotone" {...props}></Icon>
