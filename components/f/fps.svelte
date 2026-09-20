<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai4xf_p-i.css';
import '../../css/u/u-gxd5_sc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ai4xf_p-i"/><path class="u-gxd5_sc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:fps" {...props}></Icon>
