<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8b6vac3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r8b6vac3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-diagram-sharp" {...props}></Icon>
