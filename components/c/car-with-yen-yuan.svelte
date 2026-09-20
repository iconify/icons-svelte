<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rei8szb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rei8szb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:car-with-yen-yuan" {...props}></Icon>
