<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de1slkgpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="de1slkgpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:external-link-square" {...props}></Icon>
