<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln_1_ublv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ln_1_ublv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:lock-fill" {...props}></Icon>
