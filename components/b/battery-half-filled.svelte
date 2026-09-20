<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjgkwibzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wjgkwibzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:battery-half-filled" {...props}></Icon>
