<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzsnjchuv.css';
import '../../css/a/a_b-kq5rh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mzsnjchuv"/><path class="a_b-kq5rh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:music-rectangle-add-filled" {...props}></Icon>
