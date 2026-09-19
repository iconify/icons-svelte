<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8my8xg2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8my8xg2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:opera" {...props}></Icon>
