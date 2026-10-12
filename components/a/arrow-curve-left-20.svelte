<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7-6yq52x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w7-6yq52x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-curve-left-20" {...props}></Icon>
