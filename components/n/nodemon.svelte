<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m337tz4ru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="m337tz4ru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:nodemon" {...props}></Icon>
