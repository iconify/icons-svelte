<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz4_77bbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bz4_77bbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:godaddy" {...props}></Icon>
