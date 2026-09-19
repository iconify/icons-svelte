<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq-zceb_w.css';
import '../../css/r/rhd8cdczy.css';
import '../../css/w/wuev9cbck.css';
import '../../css/g/gjeb820rg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lq-zceb_w"/><path class="rhd8cdczy"/><path class="wuev9cbck"/><circle class="gjeb820rg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-aiops-insights" {...props}></Icon>
