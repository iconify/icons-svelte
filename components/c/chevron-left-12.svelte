<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdxi4ubed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="qdxi4ubed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:chevron-left-12" {...props}></Icon>
