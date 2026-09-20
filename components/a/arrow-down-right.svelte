<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xoimldhit.css';
import '../../css/p/plk93bc0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xoimldhit"/><path class="plk93bc0q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:arrow-down-right" {...props}></Icon>
