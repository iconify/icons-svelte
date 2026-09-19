<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a668dr9wo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="a668dr9wo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:jquery" {...props}></Icon>
