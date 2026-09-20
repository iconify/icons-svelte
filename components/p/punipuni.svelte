<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxkxf8z7y.css';
import '../../css/q/qiyg0hb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="yxkxf8z7y"/><path class="qiyg0hb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:punipuni" {...props}></Icon>
