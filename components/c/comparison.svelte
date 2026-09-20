<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auk_w91qr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="auk_w91qr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:comparison" {...props}></Icon>
