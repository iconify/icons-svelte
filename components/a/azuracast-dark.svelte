<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4i02jbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j4i02jbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:azuracast-dark" {...props}></Icon>
