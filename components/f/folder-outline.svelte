<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrtamebsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="folder-outline"><path class="(Stroke) Vector hrtamebsr" clip-rule="evenodd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:folder-outline" {...props}></Icon>
