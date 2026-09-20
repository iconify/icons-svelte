<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekht-vbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ekht-vbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:letter-t" {...props}></Icon>
