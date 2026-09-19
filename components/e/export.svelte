<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xoec_aceq.css';
import '../../css/b/bii24pcyv.css';
import '../../css/i/iksyp0jtl.css';
import '../../css/u/un8hgvb8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xoec_aceq"/><g class="bii24pcyv"><path class="iksyp0jtl"/><path class="un8hgvb8l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:export" {...props}></Icon>
