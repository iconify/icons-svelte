<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ueg7wcbbp.css';
import '../../css/c/coghm8bmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ueg7wcbbp"/><path clip-rule="evenodd" class="coghm8bmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:instagram-fill-24" {...props}></Icon>
