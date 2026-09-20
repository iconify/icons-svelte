<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5ry4ve3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z5ry4ve3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:arrow-turn-down-large-flat" {...props}></Icon>
