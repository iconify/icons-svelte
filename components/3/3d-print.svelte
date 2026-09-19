<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk14lcqmb.css';
import '../../css/y/ykaofac9m.css';
import '../../css/k/kdnfubntr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tk14lcqmb"/><path class="ykaofac9m"/><path clip-rule="evenodd" class="kdnfubntr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:3d-print" {...props}></Icon>
