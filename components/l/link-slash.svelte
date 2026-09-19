<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twtwy1b8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="twtwy1b8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:link-slash" {...props}></Icon>
