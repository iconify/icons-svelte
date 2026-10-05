<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o36b4-bki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="o36b4-bki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bear-and-exclamation-point" {...props}></Icon>
