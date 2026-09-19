<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7cyh0pna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l7cyh0pna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:bar" {...props}></Icon>
