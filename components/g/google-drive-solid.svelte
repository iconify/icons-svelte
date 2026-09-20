<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq8lsbcnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uq8lsbcnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:google-drive-solid" {...props}></Icon>
