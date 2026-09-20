<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3mex-bdg.css';
import '../../css/l/l-9tsmbih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3mex-bdg"/><path class="l-9tsmbih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:home-filled" {...props}></Icon>
