<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr8bqw60r.css';
import '../../css/q/qfc_s602x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cr8bqw60r"/><path class="qfc_s602x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:battery-full-minimalistic-bold" {...props}></Icon>
