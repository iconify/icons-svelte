<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okpx9ccms.css';
import '../../css/a/a59ct2b9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="okpx9ccms"/><path class="a59ct2b9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:download-bottom-bold" {...props}></Icon>
