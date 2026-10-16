<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdaustbot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1575.6,"height":1575.6,"left":82.5,"top":-157.5};
const content = `<path class="tdaustbot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mailhog" {...props}></Icon>
