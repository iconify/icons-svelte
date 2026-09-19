<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqi0cpb2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hqi0cpb2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:generate-image" {...props}></Icon>
