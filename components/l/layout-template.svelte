<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/q/qa27x5b5v.css';
import '../../css/l/lfl8g1bjv.css';
import '../../css/x/xpmt8p_bt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><rect class="qa27x5b5v"/><rect class="lfl8g1bjv"/><rect class="xpmt8p_bt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:layout-template" {...props}></Icon>
