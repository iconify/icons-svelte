<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf-3mxbdo.css';
import '../../css/e/enhfi_bcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jf-3mxbdo"/><path class="enhfi_bcu"><animateTransform attributeName="transform" dur="1s" from="0 12 12" repeatCount="indefinite" to="360 12 12" type="rotate"/></path>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:loading" {...props}></Icon>
