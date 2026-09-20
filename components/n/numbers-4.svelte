<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fccbu8b2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fccbu8b2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:numbers-4" {...props}></Icon>
