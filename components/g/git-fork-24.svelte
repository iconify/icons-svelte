<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdm9jbcnr.css';
import '../../css/e/erp-9sbvf.css';
import '../../css/m/mztshossz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdm9jbcnr"/><path class="erp-9sbvf"/><path class="mztshossz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:git-fork-24" {...props}></Icon>
