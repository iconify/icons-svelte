<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6xt5c87v.css';
import '../../css/a/a-9mugb1d.css';
import '../../css/u/up6r22q7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="j6xt5c87v"/><circle class="a-9mugb1d"/><path class="up6r22q7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:nuclear-outline" {...props}></Icon>
