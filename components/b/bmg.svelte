<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gilpv_ahg.css';
import '../../css/w/wo0pf4bui.css';
import '../../css/z/zqwds7qfz.css';
import '../../css/a/aryrtpe7w.css';
import '../../css/z/zy2q3v_mu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":105,"height":35};
const content = `<g class="gilpv_ahg"><path clip-rule="evenodd" class="wo0pf4bui"/><path class="zqwds7qfz"/><path class="aryrtpe7w"/><path class="zy2q3v_mu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bmg" {...props}></Icon>
