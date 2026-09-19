<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_kkayb9j.css';
import '../../css/i/iiryr56qr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c_kkayb9j"/><path class="iiryr56qr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:earth-southeast-asia-filled" {...props}></Icon>
