<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgl_jgbvu.css';
import '../../css/k/k_3-ad-xi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgl_jgbvu"/><path clip-rule="evenodd" class="k_3-ad-xi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cummies" {...props}></Icon>
