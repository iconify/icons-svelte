<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb33x3b4v.css';
import '../../css/h/hs1_ig4jg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary xb33x3b4v"/><path class="hs1_ig4jg primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flow-delay-duo" {...props}></Icon>
