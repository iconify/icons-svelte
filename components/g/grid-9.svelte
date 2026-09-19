<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5a8jhbxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i5a8jhbxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:grid-9" {...props}></Icon>
