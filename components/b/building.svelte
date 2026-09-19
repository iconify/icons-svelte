<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by1mcejmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="by1mcejmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:building" {...props}></Icon>
