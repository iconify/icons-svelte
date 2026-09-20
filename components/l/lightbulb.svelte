<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta7e7h-iw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ta7e7h-iw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:lightbulb" {...props}></Icon>
