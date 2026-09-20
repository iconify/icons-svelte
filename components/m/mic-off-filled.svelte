<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efqq9-b6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="efqq9-b6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:mic-off-filled" {...props}></Icon>
