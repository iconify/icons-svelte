<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok8jdmbmr.css';
import '../../css/p/pgpjlbcjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ok8jdmbmr"/><path class="pgpjlbcjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:inpatient" {...props}></Icon>
