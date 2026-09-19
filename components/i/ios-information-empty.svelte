<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6ovpccxr.css';
import '../../css/q/qume8ab4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="p6ovpccxr"/><path class="qume8ab4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-information-empty" {...props}></Icon>
