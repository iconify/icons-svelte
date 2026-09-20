<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru6sgpi9r.css';
import '../../css/a/aunmnqb4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ru6sgpi9r"/><path class="aunmnqb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:oak-identity-light" {...props}></Icon>
