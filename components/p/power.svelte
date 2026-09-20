<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn89fjbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gn89fjbgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:power" {...props}></Icon>
