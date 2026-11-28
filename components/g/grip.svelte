<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lix60osfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lix60osfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:grip" {...props}></Icon>
