<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8s26pbah.css';
import '../../css/s/s07htpbtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x8s26pbah"/><path class="s07htpbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:hurricane" {...props}></Icon>
