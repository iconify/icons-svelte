<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2v-92ycv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d2v-92ycv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-onenote-2013-light" {...props}></Icon>
