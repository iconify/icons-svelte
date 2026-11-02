<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l61jb99qf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l61jb99qf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:box-3-fill" {...props}></Icon>
