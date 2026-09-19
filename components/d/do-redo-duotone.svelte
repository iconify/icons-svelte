<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knk47snoh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knk47snoh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:do-redo-duotone" {...props}></Icon>
