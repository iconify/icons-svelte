<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt79s6bux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mt79s6bux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:crehana" {...props}></Icon>
