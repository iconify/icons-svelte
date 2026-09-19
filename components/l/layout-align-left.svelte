<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9hou_31o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a9hou_31o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:layout-align-left" {...props}></Icon>
