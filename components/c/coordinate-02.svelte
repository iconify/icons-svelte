<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/kol2iac3m.css';
import '../../css/t/t1zao4rim.css';
import '../../css/c/co2mcmbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kol2iac3m"/><path class="t1zao4rim"/><path class="co2mcmbal"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:coordinate-02" {...props}></Icon>
