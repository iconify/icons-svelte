<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jm93pvfhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jm93pvfhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:descending" {...props}></Icon>
