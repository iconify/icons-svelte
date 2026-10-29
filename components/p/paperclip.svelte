<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/my_ilnbdt.css';
import '../../css/s/sgxsvf1wu.css';
import '../../css/w/wr4ds1bix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="my_ilnbdt wm-shadow"/><path class="sgxsvf1wu wm-k"/><path class="wm-k wr4ds1bix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-pastel:paperclip" {...props}></Icon>
