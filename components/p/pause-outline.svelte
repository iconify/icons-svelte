<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myw4k0vkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="pause-outline"><path class="Vector myw4k0vkw" clip-rule="evenodd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:pause-outline" {...props}></Icon>
