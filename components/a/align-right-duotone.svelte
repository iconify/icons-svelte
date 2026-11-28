<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apimembma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="apimembma primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:align-right-duotone" {...props}></Icon>
