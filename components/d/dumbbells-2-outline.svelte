<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymv_wy09c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ymv_wy09c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dumbbells-2-outline" {...props}></Icon>
