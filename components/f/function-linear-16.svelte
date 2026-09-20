<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7ev4k4sm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b7ev4k4sm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:function-linear-16" {...props}></Icon>
