<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8j6e2bhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b8j6e2bhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:playlist-fill" {...props}></Icon>
