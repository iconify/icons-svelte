<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwxtu6bac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xwxtu6bac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-cloud-upload" {...props}></Icon>
