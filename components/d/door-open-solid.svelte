<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd6dxr9fm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qd6dxr9fm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:door-open-solid" {...props}></Icon>
