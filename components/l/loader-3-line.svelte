<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvjq8_bqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qvjq8_bqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:loader-3-line" {...props}></Icon>
