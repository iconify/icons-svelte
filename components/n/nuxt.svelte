<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh7eomlnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mh7eomlnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:nuxt" {...props}></Icon>
