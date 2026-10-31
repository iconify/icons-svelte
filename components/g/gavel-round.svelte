<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp0dh-beu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jp0dh-beu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:gavel-round" {...props}></Icon>
