<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0h3ws6gp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0h3ws6gp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:cli" {...props}></Icon>
