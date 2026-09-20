<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9fx__esr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z9fx__esr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dog-sitting-wearing-collar-and-heart" {...props}></Icon>
