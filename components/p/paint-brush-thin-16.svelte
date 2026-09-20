<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdou5jn5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mdou5jn5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:paint-brush-thin-16" {...props}></Icon>
