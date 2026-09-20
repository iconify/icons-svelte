<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z917-eb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":163.38};
const content = `<path class="z917-eb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nickelodeon" {...props}></Icon>
