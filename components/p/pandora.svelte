<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifzgxzbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifzgxzbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:pandora" {...props}></Icon>
