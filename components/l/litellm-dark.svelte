<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_y277zwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b_y277zwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:litellm-dark" {...props}></Icon>
