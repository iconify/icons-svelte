<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2v5b6b-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2v5b6b-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:font-color-filled" {...props}></Icon>
