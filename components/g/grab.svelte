<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v20lpbcwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":680,"height":694};
const content = `<path class="v20lpbcwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:grab" {...props}></Icon>
