<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pipk6ibqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pipk6ibqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:link" {...props}></Icon>
