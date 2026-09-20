<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj_-k2_7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="oj_-k2_7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:clipboard-add-remix" {...props}></Icon>
