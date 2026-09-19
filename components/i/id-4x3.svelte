<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-5uilbhv.css';
import '../../css/i/i2ddjlrtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="m-5uilbhv"/><path class="i2ddjlrtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:id-4x3" {...props}></Icon>
