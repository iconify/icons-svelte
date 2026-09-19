<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyx3ri51p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tyx3ri51p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-power" {...props}></Icon>
