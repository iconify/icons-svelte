<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yq7e4ibxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yq7e4ibxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:alarm-off" {...props}></Icon>
