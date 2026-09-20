<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzu3tqzwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lzu3tqzwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:fork-16" {...props}></Icon>
