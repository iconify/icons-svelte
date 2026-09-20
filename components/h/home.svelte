<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt1-cgxfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tt1-cgxfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:home" {...props}></Icon>
