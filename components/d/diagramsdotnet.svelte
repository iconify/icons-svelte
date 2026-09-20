<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iein70b1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iein70b1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:diagramsdotnet" {...props}></Icon>
