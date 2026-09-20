<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/seti68b8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-6};
const content = `<path class="seti68b8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:battery-charging" {...props}></Icon>
