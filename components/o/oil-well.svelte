<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urww_pbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="urww_pbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:oil-well" {...props}></Icon>
