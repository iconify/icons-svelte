<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdjiz7b1s.css';
import '../../css/t/tx7dcyx9v.css';
import '../../css/k/k-6z9bsqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pdjiz7b1s"/><path class="tx7dcyx9v"/><path class="k-6z9bsqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:monitor-camera-bold-duotone" {...props}></Icon>
