<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5ztflwgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5ztflwgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:data" {...props}></Icon>
