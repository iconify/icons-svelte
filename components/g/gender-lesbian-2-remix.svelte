<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsk20ca5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rsk20ca5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:gender-lesbian-2-remix" {...props}></Icon>
