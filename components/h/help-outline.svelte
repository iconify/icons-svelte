<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/oxfyl1b5k.css';
import '../../css/e/ewzk12bfc.css';
import '../../css/l/lkta0p-5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="help-outline"><g class="Vector cuyn6tgcc"><path clip-rule="evenodd" class="oxfyl1b5k"/><path class="ewzk12bfc"/><path clip-rule="evenodd" class="lkta0p-5n"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:help-outline" {...props}></Icon>
