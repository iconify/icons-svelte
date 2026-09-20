<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/el94-sgza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="el94-sgza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:actigraph" {...props}></Icon>
