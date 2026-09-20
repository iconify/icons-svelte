<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thas5ub-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="thas5ub-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:erlenmeyer-flask-remix" {...props}></Icon>
