<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk8010bfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pk8010bfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:restart-bold" {...props}></Icon>
