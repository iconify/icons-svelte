<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm6odxb_u.css';
import '../../css/r/rivw31b0j.css';
import '../../css/u/u4hlkiabp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lm6odxb_u"/><path class="rivw31b0j"/><path class="u4hlkiabp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:night-landscape" {...props}></Icon>
