<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvmpzpbvf.css';
import '../../css/v/vqmwm_bhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pvmpzpbvf"/><path class="vqmwm_bhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:eye-24" {...props}></Icon>
