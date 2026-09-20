<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nttp5bcbi.css';
import '../../css/u/uzxqaob3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nttp5bcbi"/><path class="uzxqaob3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:citibank" {...props}></Icon>
