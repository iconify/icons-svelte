<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zaff0bcie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zaff0bcie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-charging-80" {...props}></Icon>
