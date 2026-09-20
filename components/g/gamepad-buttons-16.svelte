<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3howiosv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v3howiosv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:gamepad-buttons-16" {...props}></Icon>
