<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3ab1hb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3ab1hb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:dovetail" {...props}></Icon>
