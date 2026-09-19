<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/echiehj1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="echiehj1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:fire" {...props}></Icon>
