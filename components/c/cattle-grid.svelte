<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zij3g3brr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zij3g3brr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:cattle-grid" {...props}></Icon>
