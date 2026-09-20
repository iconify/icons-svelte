<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlemfdc9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tlemfdc9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:bitbucket" {...props}></Icon>
