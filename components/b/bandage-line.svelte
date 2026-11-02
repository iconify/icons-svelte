<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emcn7xcoh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="emcn7xcoh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bandage-line" {...props}></Icon>
