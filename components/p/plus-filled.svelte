<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek91jiboj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ek91jiboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:plus-filled" {...props}></Icon>
