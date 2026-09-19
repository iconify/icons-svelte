<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi-b3jbuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="oi-b3jbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:film-16-solid" {...props}></Icon>
