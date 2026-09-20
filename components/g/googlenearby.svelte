<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz3pnrlyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jz3pnrlyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:googlenearby" {...props}></Icon>
