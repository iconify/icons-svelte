<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkbw6_bzt.css';
import '../../css/t/toym7nb7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="dkbw6_bzt"/><path class="toym7nb7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:hook" {...props}></Icon>
