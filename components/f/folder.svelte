<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-21fi9kw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m-21fi9kw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:folder" {...props}></Icon>
