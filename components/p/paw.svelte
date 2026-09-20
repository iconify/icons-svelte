<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/px-gk6trz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="px-gk6trz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:paw" {...props}></Icon>
