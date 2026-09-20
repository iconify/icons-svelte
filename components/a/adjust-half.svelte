<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-_j0scof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-_j0scof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:adjust-half" {...props}></Icon>
