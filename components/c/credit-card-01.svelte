<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfcst0bpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qfcst0bpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:credit-card-01" {...props}></Icon>
