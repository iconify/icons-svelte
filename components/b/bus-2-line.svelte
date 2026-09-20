<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-5jvhavy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-5jvhavy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bus-2-line" {...props}></Icon>
