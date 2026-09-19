<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izoaahe4v.css';
import '../../css/z/zrb4p4b7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="izoaahe4v"/><path class="zrb4p4b7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:notepage" {...props}></Icon>
