<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzzp8s6ii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzzp8s6ii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:navigation" {...props}></Icon>
