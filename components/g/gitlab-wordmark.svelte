<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbv3kq73b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xbv3kq73b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:gitlab-wordmark" {...props}></Icon>
