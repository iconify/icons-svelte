<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fka7ssbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="menu-outline"><path class="(Stroke) 38 Vector fka7ssbnm" clip-rule="evenodd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:menu-outline" {...props}></Icon>
