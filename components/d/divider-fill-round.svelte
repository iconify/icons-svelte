<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gd18994yc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gd18994yc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:divider-fill-round" {...props}></Icon>
