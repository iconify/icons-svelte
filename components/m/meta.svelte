<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-ivx_rnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-ivx_rnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:meta" {...props}></Icon>
