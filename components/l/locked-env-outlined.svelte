<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlzjfpbie.css';
import '../../css/w/wode1sbbf.css';
import '../../css/t/t3m92_bgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rlzjfpbie"/><path class="wode1sbbf"/><path class="t3m92_bgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:locked-env-outlined" {...props}></Icon>
