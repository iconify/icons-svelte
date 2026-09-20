<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6r-78yyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="i6r-78yyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:pills" {...props}></Icon>
