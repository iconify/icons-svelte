<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgkjp6s0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qgkjp6s0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:lock-password-solid" {...props}></Icon>
