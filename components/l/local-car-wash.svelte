<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pip8p3bjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":480};
const content = `<path class="pip8p3bjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:local-car-wash" {...props}></Icon>
