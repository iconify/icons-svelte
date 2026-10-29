<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcnyyb28t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcnyyb28t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:hard-drive-solid" {...props}></Icon>
