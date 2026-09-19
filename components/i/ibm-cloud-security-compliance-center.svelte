<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5_6rlexd.css';
import '../../css/x/xgumicc2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p5_6rlexd"/><path class="xgumicc2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-security-compliance-center" {...props}></Icon>
