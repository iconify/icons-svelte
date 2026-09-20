<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdk1bkb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gdk1bkb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:alliedmodders" {...props}></Icon>
