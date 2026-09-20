<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqyykw1dq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nqyykw1dq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:brightness-3" {...props}></Icon>
