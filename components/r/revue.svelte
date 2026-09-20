<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk9sf0-9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sk9sf0-9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:revue" {...props}></Icon>
