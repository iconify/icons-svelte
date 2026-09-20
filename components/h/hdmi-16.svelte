<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpr1pgalx.css';
import '../../css/o/ov5vkel-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kpr1pgalx"/><path clip-rule="evenodd" class="ov5vkel-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:hdmi-16" {...props}></Icon>
