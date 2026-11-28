<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-ou4dz9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-ou4dz9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:link" {...props}></Icon>
