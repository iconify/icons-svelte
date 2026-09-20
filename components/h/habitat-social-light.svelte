<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x04di0hqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x04di0hqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:habitat-social-light" {...props}></Icon>
