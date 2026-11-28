<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyjkqb7xa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hyjkqb7xa primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:hash-duotone" {...props}></Icon>
