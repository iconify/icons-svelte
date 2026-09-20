<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwrvjmo0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mwrvjmo0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nba" {...props}></Icon>
