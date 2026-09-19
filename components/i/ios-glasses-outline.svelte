<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3824zb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g3824zb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-glasses-outline" {...props}></Icon>
