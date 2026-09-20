<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwx9zx2bw.css';
import '../../css/o/ohisqfb5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gwx9zx2bw"/><path class="ohisqfb5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:gamepad-button-top-16" {...props}></Icon>
