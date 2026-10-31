<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb37rxb6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eb37rxb6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:number-9-duotone-round" {...props}></Icon>
