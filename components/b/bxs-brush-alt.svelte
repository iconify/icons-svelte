<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm-2y4n6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sm-2y4n6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-brush-alt" {...props}></Icon>
