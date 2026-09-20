<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-8tu9-dm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-8tu9-dm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrows-diagonal-minimize-2" {...props}></Icon>
