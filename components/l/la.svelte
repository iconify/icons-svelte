<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9v_qkbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g9v_qkbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:la" {...props}></Icon>
