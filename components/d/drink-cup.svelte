<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl_9n0bxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jl_9n0bxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:drink-cup" {...props}></Icon>
