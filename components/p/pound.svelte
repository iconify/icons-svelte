<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_fcprbmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p_fcprbmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:pound" {...props}></Icon>
