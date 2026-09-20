<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcwudk0gy.css';
import '../../css/s/sn54l82wk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcwudk0gy"/><path class="sn54l82wk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:go" {...props}></Icon>
