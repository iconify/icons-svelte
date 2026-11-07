<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjjac2bhg.css';
import '../../css/e/egvbavgae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qjjac2bhg"/><path clip-rule="evenodd" class="egvbavgae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:copy-check-outline" {...props}></Icon>
