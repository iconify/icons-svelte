<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/excf6z61k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="excf6z61k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cartoon-bomb-with-lit-fuse" {...props}></Icon>
