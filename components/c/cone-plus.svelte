<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br25d5blh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="br25d5blh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cone-plus" {...props}></Icon>
