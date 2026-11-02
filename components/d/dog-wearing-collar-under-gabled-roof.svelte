<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clvc58_0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="clvc58_0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dog-wearing-collar-under-gabled-roof" {...props}></Icon>
