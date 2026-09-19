<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twkvrxbyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="twkvrxbyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bookmark-alt-filled" {...props}></Icon>
