<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yth0o7dpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yth0o7dpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:mirror2" {...props}></Icon>
