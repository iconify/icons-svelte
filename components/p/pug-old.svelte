<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv3bzacig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fv3bzacig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:pug-old" {...props}></Icon>
