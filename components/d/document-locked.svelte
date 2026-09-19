<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzkoekz4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xzkoekz4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:document-locked" {...props}></Icon>
