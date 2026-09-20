<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9i4nfbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d9i4nfbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:cloud-add-remix" {...props}></Icon>
