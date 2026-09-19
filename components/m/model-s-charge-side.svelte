<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5vac479p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y5vac479p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:model-s-charge-side" {...props}></Icon>
