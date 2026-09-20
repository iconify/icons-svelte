<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fimbogbso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fimbogbso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:refresh" {...props}></Icon>
