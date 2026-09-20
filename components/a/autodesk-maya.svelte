<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou0ltpy1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ou0ltpy1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:autodesk-maya" {...props}></Icon>
