<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw-0snbeq.css';
import '../../css/w/w-hibw8hw.css';
import '../../css/x/xeb9n_bni.css';
import '../../css/v/vux753b6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fw-0snbeq"/><path class="ouiIcon__fillSecondary w-hibw8hw"/><path class="xeb9n_bni"/><path class="ouiIcon__fillSecondary vux753b6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-dashboard" {...props}></Icon>
