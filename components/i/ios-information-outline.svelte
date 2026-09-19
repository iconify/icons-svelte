<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6ovpccxr.css';
import '../../css/q/qume8ab4m.css';
import '../../css/i/itc5zdbai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="p6ovpccxr"/><path class="qume8ab4m"/><g><path class="itc5zdbai"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-information-outline" {...props}></Icon>
