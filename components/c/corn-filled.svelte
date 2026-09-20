<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik4pm6qxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ik4pm6qxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:corn-filled" {...props}></Icon>
