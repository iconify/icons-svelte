<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpgq7rm-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bpgq7rm-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:present-16" {...props}></Icon>
