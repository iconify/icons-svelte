<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tebz53gcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tebz53gcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:apachespark" {...props}></Icon>
