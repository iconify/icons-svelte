<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guv2ysbiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="guv2ysbiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:mobile" {...props}></Icon>
