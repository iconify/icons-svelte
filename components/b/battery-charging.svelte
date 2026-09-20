<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxg2k8bsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxg2k8bsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:battery-charging" {...props}></Icon>
