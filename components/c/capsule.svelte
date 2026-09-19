<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2wh_732m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="k2wh_732m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:capsule" {...props}></Icon>
