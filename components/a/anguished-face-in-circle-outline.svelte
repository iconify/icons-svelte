<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-9ae1okw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="x-9ae1okw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:anguished-face-in-circle-outline" {...props}></Icon>
