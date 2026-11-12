<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1d7chbrz.css';
import '../../css/q/qiyg0hb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="b1d7chbrz"/><path class="qiyg0hb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:punipuni" {...props}></Icon>
