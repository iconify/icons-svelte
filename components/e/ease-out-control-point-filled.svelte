<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h69xeeoun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h69xeeoun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ease-out-control-point-filled" {...props}></Icon>
