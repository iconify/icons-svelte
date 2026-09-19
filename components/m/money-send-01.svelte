<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/i/igh-6877r.css';
import '../../css/g/g48w89bvm.css';
import '../../css/h/hnlb0b7xy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="igh-6877r"/><path class="g48w89bvm"/><path class="hnlb0b7xy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:money-send-01" {...props}></Icon>
