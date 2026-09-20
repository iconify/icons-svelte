<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh-v-bczu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dh-v-bczu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dailytxt-dark" {...props}></Icon>
