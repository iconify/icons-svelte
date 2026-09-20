<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpqw4q6qk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rpqw4q6qk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cnes" {...props}></Icon>
