<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdlysac4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kdlysac4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dog-sitting-wearing-collar-and-exclamation-point" {...props}></Icon>
