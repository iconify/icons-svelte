<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3-zj-h9b.css';
import '../../css/s/sbjtnhxpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3-zj-h9b"/><path class="sbjtnhxpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:play-circle" {...props}></Icon>
