<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urlauhbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="urlauhbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:nordicsemiconductor" {...props}></Icon>
