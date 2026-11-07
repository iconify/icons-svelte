<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/u/ubpbu9mrb.css';
import '../../css/t/t1in8db2h.css';
import '../../css/s/s41he0bba.css';
import '../../css/m/m-5zcvb8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ubpbu9mrb"/><path class="t1in8db2h"/><path class="s41he0bba"/><path class="m-5zcvb8c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hashtag-broken" {...props}></Icon>
