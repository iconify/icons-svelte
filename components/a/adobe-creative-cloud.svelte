<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrgrc1b7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrgrc1b7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:adobe-creative-cloud" {...props}></Icon>
