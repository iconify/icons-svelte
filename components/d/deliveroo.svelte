<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1pcwab3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1pcwab3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:deliveroo" {...props}></Icon>
