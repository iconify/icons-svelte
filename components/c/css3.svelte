<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/siphky6-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="siphky6-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:css3" {...props}></Icon>
