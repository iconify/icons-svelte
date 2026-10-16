<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa_132r-y.css';
import '../../css/i/ihmii9b0s.css';
import '../../css/t/tiqwyoept.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qa_132r-y"/><path class="ihmii9b0s"/><path class="tiqwyoept"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:containment-dome-48-bold" {...props}></Icon>
