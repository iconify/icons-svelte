<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku3j7y3ue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ku3j7y3ue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-arrows-left-right-above-water" {...props}></Icon>
