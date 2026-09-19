<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5yy7fx-i.css';
import '../../css/p/puf8leb7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j5yy7fx-i"/><path class="puf8leb7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:opentofu" {...props}></Icon>
