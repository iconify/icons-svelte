<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd7besbrf.css';
import '../../css/k/kgg90w3zy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wd7besbrf"/><path class="kgg90w3zy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:map-information-filled" {...props}></Icon>
