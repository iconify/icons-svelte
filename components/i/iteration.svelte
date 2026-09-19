<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxj7ol8dj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxj7ol8dj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:iteration" {...props}></Icon>
