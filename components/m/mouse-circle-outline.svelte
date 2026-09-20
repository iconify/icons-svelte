<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_ofi4dze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x_ofi4dze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mouse-circle-outline" {...props}></Icon>
