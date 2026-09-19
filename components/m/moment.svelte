<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha1ke4byu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ha1ke4byu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:moment" {...props}></Icon>
