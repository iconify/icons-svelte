<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt-vzwbpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lt-vzwbpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:revert" {...props}></Icon>
