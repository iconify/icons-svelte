<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umlnqi5-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="umlnqi5-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:bold" {...props}></Icon>
