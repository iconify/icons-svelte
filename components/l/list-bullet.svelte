<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr7_cdb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="qr7_cdb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:list-bullet" {...props}></Icon>
