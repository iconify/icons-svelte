<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtnme21ja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="vtnme21ja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:heart" {...props}></Icon>
