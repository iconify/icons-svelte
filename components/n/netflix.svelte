<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qiqu0vbdz.css';
import '../../css/s/sjfxabblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qiqu0vbdz"/><path class="sjfxabblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:netflix" {...props}></Icon>
