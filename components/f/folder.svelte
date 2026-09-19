<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_bhexbuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_bhexbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:folder" {...props}></Icon>
