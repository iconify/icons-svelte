<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv0je9-js.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tv0je9-js"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:infosys" {...props}></Icon>
