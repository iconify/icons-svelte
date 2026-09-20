<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlifw3buw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xlifw3buw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mini" {...props}></Icon>
