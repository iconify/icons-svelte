<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1gqgyb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":455,"height":512};
const content = `<path class="k1gqgyb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:c" {...props}></Icon>
