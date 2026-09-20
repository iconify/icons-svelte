<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub-rgf-9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ub-rgf-9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rear-windshield-defroster-fill" {...props}></Icon>
