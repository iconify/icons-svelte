<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umtprzi3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="umtprzi3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:hourglass" {...props}></Icon>
