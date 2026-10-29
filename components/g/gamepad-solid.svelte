<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn0jcekjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qn0jcekjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:gamepad-solid" {...props}></Icon>
