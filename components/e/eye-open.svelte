<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/c/c70u1_9qk.css';
import '../../css/y/y_nsz_h-y.css';
import '../../css/g/gzhzl4bww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c70u1_9qk"/><circle class="y_nsz_h-y"/><path class="gzhzl4bww"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:eye-open" {...props}></Icon>
