<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnul7o5fb.css';
import '../../css/p/pr_1mzb5o.css';
import '../../css/l/lxli7kbnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bnul7o5fb"/><circle class="pr_1mzb5o"/><path class="lxli7kbnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-hyper-protect-crypto-services" {...props}></Icon>
