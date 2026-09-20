<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk64cac5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yk64cac5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:mars" {...props}></Icon>
