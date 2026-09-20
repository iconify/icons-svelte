<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfoehcc9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfoehcc9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:pear-filled" {...props}></Icon>
