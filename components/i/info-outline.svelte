<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/oxfyl1b5k.css';
import '../../css/g/g-1ion60j.css';
import '../../css/v/vz812pbmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="info-outline"><g class="Vector cuyn6tgcc"><path clip-rule="evenodd" class="oxfyl1b5k"/><path clip-rule="evenodd" class="g-1ion60j"/><path class="vz812pbmd"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:info-outline" {...props}></Icon>
