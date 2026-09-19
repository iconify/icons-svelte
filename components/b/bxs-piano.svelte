<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqb1-0mmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqb1-0mmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-piano" {...props}></Icon>
