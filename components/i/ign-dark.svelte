<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bs2fs5bky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bs2fs5bky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ign-dark" {...props}></Icon>
