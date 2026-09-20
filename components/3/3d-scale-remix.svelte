<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7rwwgb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w7rwwgb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:3d-scale-remix" {...props}></Icon>
