<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjfcwybnl.css';
import '../../css/v/vrncrobzx.css';
import '../../css/k/ki4mvymot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjfcwybnl"/><path class="vrncrobzx"/><path class="ki4mvymot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:jquery" {...props}></Icon>
