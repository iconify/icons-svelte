<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmr2wt9_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zmr2wt9_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:input-box-remix" {...props}></Icon>
