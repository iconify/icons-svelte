<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnq21wbic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="wnq21wbic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:align-text-right-solid" {...props}></Icon>
