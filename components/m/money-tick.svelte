<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/l/lh6ix6bdu.css';
import '../../css/h/hfz_8abyz.css';
import '../../css/x/xme47371x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lh6ix6bdu"/><path class="hfz_8abyz"/><path class="xme47371x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:money-tick" {...props}></Icon>
