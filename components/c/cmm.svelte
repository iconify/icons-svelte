<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz1n9qbid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bz1n9qbid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:cmm" {...props}></Icon>
