<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq0gmnb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xq0gmnb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:paintbrush-sharp-fill" {...props}></Icon>
