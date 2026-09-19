<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4a7kh3gw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b4a7kh3gw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-flash" {...props}></Icon>
