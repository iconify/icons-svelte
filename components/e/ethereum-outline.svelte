<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1dy8tbco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f1dy8tbco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:ethereum-outline" {...props}></Icon>
