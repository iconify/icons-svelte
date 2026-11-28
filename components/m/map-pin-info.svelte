<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs0fk7e4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vs0fk7e4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:map-pin-info" {...props}></Icon>
