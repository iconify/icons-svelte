<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsitdtb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qsitdtb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:calculator-line" {...props}></Icon>
