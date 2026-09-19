<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac_vz1bhc.css';
import '../../css/z/zgk5_n2-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":24};
const content = `<path class="ac_vz1bhc"/><path class="zgk5_n2-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:metro" {...props}></Icon>
