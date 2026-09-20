<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvxd9ribf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nvxd9ribf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:medical-ribbon-1-remix" {...props}></Icon>
