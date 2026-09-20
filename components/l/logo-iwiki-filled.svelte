<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fquq4wb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fquq4wb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-iwiki-filled" {...props}></Icon>
