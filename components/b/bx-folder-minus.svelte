<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8u4nj3lr.css';
import '../../css/l/lv7a0p21m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8u4nj3lr"/><path class="lv7a0p21m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-folder-minus" {...props}></Icon>
