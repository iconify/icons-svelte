<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pt9skmbar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pt9skmbar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:p-wide-under-roof" {...props}></Icon>
