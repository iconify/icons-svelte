<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc8u2wqpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dc8u2wqpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:document-pdf" {...props}></Icon>
