<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2l086bip.css';
import '../../css/i/iqk83abwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l2l086bip"/><path class="iqk83abwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:egg-fried" {...props}></Icon>
