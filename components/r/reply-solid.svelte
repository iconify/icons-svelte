<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxaaq9i5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxaaq9i5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:reply-solid" {...props}></Icon>
