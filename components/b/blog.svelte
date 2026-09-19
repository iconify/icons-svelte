<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bipx84bst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bipx84bst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:blog" {...props}></Icon>
