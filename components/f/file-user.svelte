<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/c/c73e0yd1g.css';
import '../../css/s/s-37tkb2d.css';
import '../../css/y/ykzxdyblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c73e0yd1g"/><path class="s-37tkb2d"/><path class="ykzxdyblb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:file-user" {...props}></Icon>
