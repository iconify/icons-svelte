<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdm0-fbdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pdm0-fbdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:number-8" {...props}></Icon>
