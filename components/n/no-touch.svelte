<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-d5anb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-d5anb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:no-touch" {...props}></Icon>
