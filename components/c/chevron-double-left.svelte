<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmdhl3beh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmdhl3beh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:chevron-double-left" {...props}></Icon>
