<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqukjzb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="xqukjzb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:person-crop-circle-fill-badge-plus" {...props}></Icon>
