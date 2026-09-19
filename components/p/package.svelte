<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sujvg4r4g.css';
import '../../css/x/xijg6zb7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sujvg4r4g"/><path class="xijg6zb7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:package" {...props}></Icon>
