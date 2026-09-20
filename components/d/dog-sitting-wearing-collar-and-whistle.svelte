<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei6q48z0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ei6q48z0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dog-sitting-wearing-collar-and-whistle" {...props}></Icon>
