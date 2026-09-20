<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brfbl6fbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="brfbl6fbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:eye-crossed-16" {...props}></Icon>
