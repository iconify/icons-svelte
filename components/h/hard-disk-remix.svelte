<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2zn-v2ix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="o2zn-v2ix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hard-disk-remix" {...props}></Icon>
