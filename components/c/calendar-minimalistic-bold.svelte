<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbzkg2bkw.css';
import '../../css/e/e_29zdb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dbzkg2bkw"/><path class="e_29zdb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:calendar-minimalistic-bold" {...props}></Icon>
