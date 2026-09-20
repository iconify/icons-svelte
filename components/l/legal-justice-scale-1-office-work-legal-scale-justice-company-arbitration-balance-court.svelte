<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9whj-l1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="g9whj-l1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:legal-justice-scale-1-office-work-legal-scale-justice-company-arbitration-balance-court" {...props}></Icon>
