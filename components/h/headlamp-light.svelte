<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezzg8ab2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ezzg8ab2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:headlamp-light" {...props}></Icon>
