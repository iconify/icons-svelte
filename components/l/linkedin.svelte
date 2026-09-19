<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqt9-9byr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqt9-9byr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:linkedin" {...props}></Icon>
