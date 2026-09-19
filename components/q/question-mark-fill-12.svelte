<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm51gobgi.css';
import '../../css/t/tz-ovhbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="tm51gobgi"/><circle class="tz-ovhbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:question-mark-fill-12" {...props}></Icon>
