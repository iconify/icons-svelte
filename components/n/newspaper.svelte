<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cit49lbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="cit49lbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:newspaper" {...props}></Icon>
