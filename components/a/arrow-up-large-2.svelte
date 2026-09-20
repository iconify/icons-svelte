<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmz8e061p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmz8e061p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:arrow-up-large-2" {...props}></Icon>
