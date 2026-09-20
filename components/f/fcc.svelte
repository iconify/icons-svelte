<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbafqqb-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbafqqb-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:fcc" {...props}></Icon>
