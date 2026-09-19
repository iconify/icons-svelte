<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr_un4bow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sr_un4bow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:polymer" {...props}></Icon>
