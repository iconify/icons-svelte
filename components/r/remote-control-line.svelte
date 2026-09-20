<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvvcmoqrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvvcmoqrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:remote-control-line" {...props}></Icon>
