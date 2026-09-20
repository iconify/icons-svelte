<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t19d__biu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":222};
const content = `<path class="t19d__biu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:material-ui" {...props}></Icon>
