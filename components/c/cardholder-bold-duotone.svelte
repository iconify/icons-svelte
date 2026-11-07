<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg928d-qd.css';
import '../../css/p/pdhevyb1i.css';
import '../../css/t/txy1lntoa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vg928d-qd"/><path class="pdhevyb1i"/><path class="txy1lntoa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cardholder-bold-duotone" {...props}></Icon>
