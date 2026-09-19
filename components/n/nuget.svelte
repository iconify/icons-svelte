<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un-wte4cx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="un-wte4cx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:nuget" {...props}></Icon>
