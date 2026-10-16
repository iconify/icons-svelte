<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob01ca7jx.css';
import '../../css/f/f_4nudb1i.css';
import '../../css/n/nzv-bubbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ob01ca7jx"/><path class="f_4nudb1i"/><path class="nzv-bubbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:desertification-20-bold" {...props}></Icon>
