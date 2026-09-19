<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq0d9e_tb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gq0d9e_tb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:anchor" {...props}></Icon>
