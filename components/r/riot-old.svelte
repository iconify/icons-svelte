<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puaxb3bpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="puaxb3bpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:riot-old" {...props}></Icon>
