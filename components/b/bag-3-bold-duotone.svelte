<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxjhjgbtl.css';
import '../../css/k/kcmyxgenc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxjhjgbtl"/><path class="kcmyxgenc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bag-3-bold-duotone" {...props}></Icon>
