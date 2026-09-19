<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6-xxm_2j.css';
import '../../css/q/qk15utbtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6-xxm_2j"/><path class="qk15utbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cricket-ball" {...props}></Icon>
