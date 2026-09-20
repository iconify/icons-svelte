<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b15kgtb8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b15kgtb8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:film-roll-16" {...props}></Icon>
