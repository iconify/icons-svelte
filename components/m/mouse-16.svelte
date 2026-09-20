<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1er3c68j.css';
import '../../css/d/dmrek5bey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j1er3c68j"/><path clip-rule="evenodd" class="dmrek5bey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:mouse-16" {...props}></Icon>
