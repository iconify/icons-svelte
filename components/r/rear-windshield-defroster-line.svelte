<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmkwfobfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lmkwfobfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rear-windshield-defroster-line" {...props}></Icon>
