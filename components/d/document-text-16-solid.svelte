<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztazg6i9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ztazg6i9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-text-16-solid" {...props}></Icon>
