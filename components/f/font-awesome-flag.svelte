<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjiajobrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zjiajobrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:font-awesome-flag" {...props}></Icon>
