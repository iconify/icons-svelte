<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjic3kb-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kjic3kb-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:police-15" {...props}></Icon>
