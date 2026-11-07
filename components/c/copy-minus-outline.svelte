<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckns9ub6x.css';
import '../../css/e/egvbavgae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ckns9ub6x"/><path clip-rule="evenodd" class="egvbavgae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:copy-minus-outline" {...props}></Icon>
