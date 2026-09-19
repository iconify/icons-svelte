<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv6t6jgex.css';
import '../../css/j/j8hf9v3cp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xv6t6jgex"/><path class="j8hf9v3cp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-secrets-manager" {...props}></Icon>
