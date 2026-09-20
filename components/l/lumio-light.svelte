<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r22fqh72r.css';
import '../../css/o/o4k3kffuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r22fqh72r"/><path class="o4k3kffuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lumio-light" {...props}></Icon>
