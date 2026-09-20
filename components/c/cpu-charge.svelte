<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/n/n47rxdneh.css';
import '../../css/s/s6ae1bchi.css';
import '../../css/h/hbg0kobxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n47rxdneh"/><path class="s6ae1bchi"/><path class="hbg0kobxj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cpu-charge" {...props}></Icon>
