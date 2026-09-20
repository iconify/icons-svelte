<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfu3-dmkg.css';
import '../../css/a/aukw43xsk.css';
import '../../css/q/qy58zchov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xfu3-dmkg"/><path class="aukw43xsk"/><path clip-rule="evenodd" class="qy58zchov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:gpu-16" {...props}></Icon>
