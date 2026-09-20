<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rigzz57ml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rigzz57ml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:closet2" {...props}></Icon>
