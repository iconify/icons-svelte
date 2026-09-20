<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfdi0b5fr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfdi0b5fr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:arrow-thick-left-3-bold" {...props}></Icon>
