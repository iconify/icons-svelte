<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvbv0eb9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvbv0eb9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cursor-dashed-panel-sharp" {...props}></Icon>
