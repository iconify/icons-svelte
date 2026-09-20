<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp6l9nbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":35,"height":32};
const content = `<path class="jp6l9nbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bonusly" {...props}></Icon>
