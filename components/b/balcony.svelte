<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o96j-bnpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o96j-bnpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:balcony" {...props}></Icon>
