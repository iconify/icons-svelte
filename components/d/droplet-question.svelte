<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/is2b7bcwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="is2b7bcwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:droplet-question" {...props}></Icon>
