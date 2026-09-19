<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td2qqkb6u.css';
import '../../css/w/w6198jjkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="td2qqkb6u"/><path class="w6198jjkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:barcode-reader" {...props}></Icon>
