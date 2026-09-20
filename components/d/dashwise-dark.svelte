<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as7t9kaju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="as7t9kaju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dashwise-dark" {...props}></Icon>
