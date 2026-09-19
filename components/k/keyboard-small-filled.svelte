<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/porap235f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="porap235f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keyboard-small-filled" {...props}></Icon>
