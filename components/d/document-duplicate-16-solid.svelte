<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gro_6ubgm.css';
import '../../css/b/b59azjj9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gro_6ubgm"/><path class="b59azjj9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-duplicate-16-solid" {...props}></Icon>
