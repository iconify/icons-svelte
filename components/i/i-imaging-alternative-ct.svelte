<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4porcctd.css';
import '../../css/e/egn_lcc1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="g4porcctd"/><path class="egn_lcc1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-imaging-alternative-ct" {...props}></Icon>
