<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a59uvoboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a59uvoboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:battery-empty2-filled" {...props}></Icon>
