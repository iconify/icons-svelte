<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/v/v9d36vgse.css';
import '../../css/o/oxkfxll7r.css';
import '../../css/q/qozean2np.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v9d36vgse"/><path class="oxkfxll7r"/><path class="qozean2np"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:figma" {...props}></Icon>
