<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2-1htsle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b2-1htsle"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:azuredataexplorer" {...props}></Icon>
