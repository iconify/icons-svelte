<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui36x6bmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="ui36x6bmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:hippo" {...props}></Icon>
