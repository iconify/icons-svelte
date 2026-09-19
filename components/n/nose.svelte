<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnwdegbso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qnwdegbso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:nose" {...props}></Icon>
