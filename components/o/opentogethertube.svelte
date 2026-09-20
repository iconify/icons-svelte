<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9sl7lbit.css';
import '../../css/x/x7rph2bhw.css';
import '../../css/t/tx-4f1bjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z9sl7lbit"/><path class="x7rph2bhw"/><path class="tx-4f1bjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opentogethertube" {...props}></Icon>
