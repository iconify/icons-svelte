<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgb2efl3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hgb2efl3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:hide-layer-remix" {...props}></Icon>
