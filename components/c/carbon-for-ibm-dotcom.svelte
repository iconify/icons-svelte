<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh_nadcab.css';
import '../../css/u/ub4d63l7m.css';
import '../../css/k/k43y_he5a.css';
import '../../css/k/kaisiyc_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gh_nadcab"/><circle class="ub4d63l7m"/><circle class="k43y_he5a"/><path class="kaisiyc_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:carbon-for-ibm-dotcom" {...props}></Icon>
