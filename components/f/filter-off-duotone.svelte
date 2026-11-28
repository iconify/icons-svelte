<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-wdsq-6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-wdsq-6y primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:filter-off-duotone" {...props}></Icon>
