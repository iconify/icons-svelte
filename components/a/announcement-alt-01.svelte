<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbgg8ow9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tbgg8ow9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:announcement-alt-01" {...props}></Icon>
