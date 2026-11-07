<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4_uu6bes.css';
import '../../css/z/z2oj5v6-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t4_uu6bes"/><path class="z2oj5v6-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-down-from-line-bold-duotone" {...props}></Icon>
