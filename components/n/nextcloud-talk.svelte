<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/el2kicbta.css';
import '../../css/f/fs0bxbjar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="el2kicbta"/><path class="fs0bxbjar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-talk" {...props}></Icon>
