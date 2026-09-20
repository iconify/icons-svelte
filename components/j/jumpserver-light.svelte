<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2mi4d5uu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x2mi4d5uu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jumpserver-light" {...props}></Icon>
