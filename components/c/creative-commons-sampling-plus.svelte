<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frzdw0c2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="frzdw0c2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:creative-commons-sampling-plus" {...props}></Icon>
