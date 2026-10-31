<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-ao8x7sy.css';
import '../../css/r/r9m45djyc.css';
import '../../css/t/tlm5y69ci.css';
import '../../css/s/sc_6ohbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="v-ao8x7sy"/><path class="r9m45djyc"/><path class="tlm5y69ci"/><path class="sc_6ohbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:chile" {...props}></Icon>
