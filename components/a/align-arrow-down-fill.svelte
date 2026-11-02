<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd-9u1kxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kd-9u1kxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-arrow-down-fill" {...props}></Icon>
