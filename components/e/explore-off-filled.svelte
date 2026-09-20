<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abrhsib9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abrhsib9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:explore-off-filled" {...props}></Icon>
