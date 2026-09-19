<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2zphtb3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":498,"height":512};
const content = `<path class="b2zphtb3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:eslint-old" {...props}></Icon>
