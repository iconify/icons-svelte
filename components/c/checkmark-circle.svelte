<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuedu7c-d.css';
import '../../css/p/pw002-boc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="kuedu7c-d"/><path class="pw002-boc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:checkmark-circle" {...props}></Icon>
