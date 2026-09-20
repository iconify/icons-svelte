<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0w1l3idh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p0w1l3idh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:layout-align-top-filled" {...props}></Icon>
