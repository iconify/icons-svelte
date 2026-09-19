<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we5l3ab3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="we5l3ab3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:descend" {...props}></Icon>
