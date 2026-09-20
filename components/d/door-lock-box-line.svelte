<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l92q-gx-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l92q-gx-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:door-lock-box-line" {...props}></Icon>
