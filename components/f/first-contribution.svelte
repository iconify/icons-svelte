<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axnb70bez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="axnb70bez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:first-contribution" {...props}></Icon>
