<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg1ooc8-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eg1ooc8-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:planning-center-church-center-light" {...props}></Icon>
