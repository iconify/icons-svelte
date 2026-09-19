<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mwqjmhb_t.css';
import '../../css/w/wpo6wibuz.css';
import '../../css/c/c9qeufl8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mwqjmhb_t"/><path class="wpo6wibuz"/><path class="c9qeufl8i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:dish-02" {...props}></Icon>
