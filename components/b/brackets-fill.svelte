<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjxtmvqzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zjxtmvqzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:brackets-fill" {...props}></Icon>
