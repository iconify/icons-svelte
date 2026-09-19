<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttgog_btk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ttgog_btk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:laptop" {...props}></Icon>
