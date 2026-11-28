<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbytk1gwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbytk1gwj primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:nodes-cycle-duotone" {...props}></Icon>
