<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/s/smoaa5b3r.css';
import '../../css/a/a0twn3bdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="smoaa5b3r"/><path class="a0twn3bdo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:pointers-light" {...props}></Icon>
