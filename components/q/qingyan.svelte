<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oeme7nnhw.css';
import '../../css/y/yt3wrgl6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oeme7nnhw"/><path class="yt3wrgl6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:qingyan" {...props}></Icon>
