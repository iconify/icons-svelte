<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwsie36oy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fwsie36oy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:database-remix" {...props}></Icon>
