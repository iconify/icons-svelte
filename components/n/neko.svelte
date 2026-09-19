<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx6lgub6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":486,"height":512};
const content = `<path class="lx6lgub6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:neko" {...props}></Icon>
