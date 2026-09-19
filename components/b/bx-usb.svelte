<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brtl6grdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="brtl6grdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-usb" {...props}></Icon>
