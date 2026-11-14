<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/w/w6b3lzbgx.css';
import '../../css/s/sr_zc7bwn.css';
import '../../css/d/dd5nscbtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w6b3lzbgx"/><path class="sr_zc7bwn"/><path class="dd5nscbtu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-mail" {...props}></Icon>
