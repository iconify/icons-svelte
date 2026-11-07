<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_29zdb8m.css';
import '../../css/e/ess3czbnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_29zdb8m"/><path clip-rule="evenodd" class="ess3czbnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:calendar-mark-bold" {...props}></Icon>
