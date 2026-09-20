<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8oeb6bld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g8oeb6bld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-sitting-on-bench" {...props}></Icon>
