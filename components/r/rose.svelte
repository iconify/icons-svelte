<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/k/ka33u2bhe.css';
import '../../css/o/olhvvccak.css';
import '../../css/u/uii-qib3b.css';
import '../../css/i/ivrn0gbdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ka33u2bhe"/><path class="olhvvccak"/><path class="uii-qib3b"/><circle class="ivrn0gbdm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:rose" {...props}></Icon>
