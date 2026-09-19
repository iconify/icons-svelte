<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uum-u-bol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uum-u-bol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:flask" {...props}></Icon>
