<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm80i3cgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rm80i3cgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:frame2" {...props}></Icon>
