<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oiwpa3b3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oiwpa3b3b primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chevron-right-duotone" {...props}></Icon>
