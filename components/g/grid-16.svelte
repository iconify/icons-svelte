<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge94l3j4u.css';
import '../../css/p/p1-wg6b3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ge94l3j4u"/><path clip-rule="evenodd" class="p1-wg6b3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:grid-16" {...props}></Icon>
