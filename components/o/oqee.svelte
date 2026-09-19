<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2bx2sphf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a2bx2sphf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:oqee" {...props}></Icon>
