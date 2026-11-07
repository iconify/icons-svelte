<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wygv-re1g.css';
import '../../css/t/t6-wmjb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wygv-re1g"/><path class="t6-wmjb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:crop-bold" {...props}></Icon>
