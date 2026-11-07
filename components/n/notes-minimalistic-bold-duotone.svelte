<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2g6lqbdb.css';
import '../../css/f/fnwhem6it.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t2g6lqbdb"/><path class="fnwhem6it"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:notes-minimalistic-bold-duotone" {...props}></Icon>
