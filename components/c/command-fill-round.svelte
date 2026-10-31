<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q48-8fbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q48-8fbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:command-fill-round" {...props}></Icon>
