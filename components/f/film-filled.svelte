<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqm1_6bzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="tqm1_6bzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:film-filled" {...props}></Icon>
