<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz30t38ho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fz30t38ho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:files-landscapes" {...props}></Icon>
