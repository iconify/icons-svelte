<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlwlj-b0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="tlwlj-b0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:bookmark-plus-20-solid" {...props}></Icon>
