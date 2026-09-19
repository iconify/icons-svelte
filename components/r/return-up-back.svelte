<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzp_awbau.css';
import '../../css/n/nar_pyley.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pzp_awbau"/><path class="nar_pyley"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:return-up-back" {...props}></Icon>
