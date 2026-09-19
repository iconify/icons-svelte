<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ju3o7zbjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ju3o7zbjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:google-wallet" {...props}></Icon>
