<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgfp4ebof.css';
import '../../css/i/ipz-bu3ya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":55.425};
const content = `<rect class="pgfp4ebof"/><path class="ipz-bu3ya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:biomejs" {...props}></Icon>
