<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwpp7qaoo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xwpp7qaoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mealie-light" {...props}></Icon>
