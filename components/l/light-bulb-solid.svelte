<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d9ezus9os.css';
import '../../css/i/ih6mbqb9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="d9ezus9os"/><path clip-rule="evenodd" class="ih6mbqb9v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:light-bulb-solid" {...props}></Icon>
