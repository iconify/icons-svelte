<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv04go_lk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sv04go_lk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:mirror-filled" {...props}></Icon>
