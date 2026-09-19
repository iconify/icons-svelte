<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6l3-xb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="h6l3-xb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:avataralt" {...props}></Icon>
