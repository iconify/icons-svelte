<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h134tzmmn.css';
import '../../css/d/dwpr0mcby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="h134tzmmn"/><path class="dwpr0mcby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:data-type-string-list" {...props}></Icon>
