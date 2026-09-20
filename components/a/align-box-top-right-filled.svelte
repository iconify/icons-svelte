<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg5kujbwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zg5kujbwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:align-box-top-right-filled" {...props}></Icon>
