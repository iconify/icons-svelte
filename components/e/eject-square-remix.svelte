<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq_8xzbaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gq_8xzbaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:eject-square-remix" {...props}></Icon>
