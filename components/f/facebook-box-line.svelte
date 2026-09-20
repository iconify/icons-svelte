<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjapdh0be.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qjapdh0be"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:facebook-box-line" {...props}></Icon>
