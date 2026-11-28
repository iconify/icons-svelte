<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnp4-d4ot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary vnp4-d4ot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:barbell-duotone" {...props}></Icon>
