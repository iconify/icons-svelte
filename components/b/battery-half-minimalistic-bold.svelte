<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge4dfdclf.css';
import '../../css/q/qfc_s602x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ge4dfdclf"/><path class="qfc_s602x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:battery-half-minimalistic-bold" {...props}></Icon>
