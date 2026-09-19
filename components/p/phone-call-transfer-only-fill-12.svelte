<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrzprmb1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="nrzprmb1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:phone-call-transfer-only-fill-12" {...props}></Icon>
