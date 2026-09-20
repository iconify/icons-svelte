<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sg7argb-b.css';
import '../../css/g/gfaea2w_j.css';
import '../../css/i/imc05mbed.css';
import '../../css/a/a-4v7vhmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sg7argb-b"/><path class="gfaea2w_j"/><path class="imc05mbed"/><path class="a-4v7vhmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magic-stick-3-bold-duotone" {...props}></Icon>
