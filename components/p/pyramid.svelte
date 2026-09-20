<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njsk45-mo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njsk45-mo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pyramid" {...props}></Icon>
