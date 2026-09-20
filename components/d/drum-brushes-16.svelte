<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4z_23_9n.css';
import '../../css/w/w40fbby0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z4z_23_9n"/><path class="w40fbby0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:drum-brushes-16" {...props}></Icon>
