<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo7v9xb1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lo7v9xb1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:award" {...props}></Icon>
