<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsq6jsz0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tsq6jsz0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:1and1" {...props}></Icon>
