<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps04a2jte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ps04a2jte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:headphones-16" {...props}></Icon>
