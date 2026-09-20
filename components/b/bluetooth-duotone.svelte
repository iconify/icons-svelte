<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnyl9fv0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnyl9fv0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bluetooth-duotone" {...props}></Icon>
