<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh5pojbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mh5pojbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:cloud-terminal" {...props}></Icon>
