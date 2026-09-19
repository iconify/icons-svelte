<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4n8a_oym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p4n8a_oym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-arrow-dropleft-circle" {...props}></Icon>
