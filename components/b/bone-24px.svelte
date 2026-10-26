<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grcycm9of.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grcycm9of"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:bone-24px" {...props}></Icon>
