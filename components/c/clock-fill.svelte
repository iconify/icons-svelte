<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdeddab-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="hdeddab-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:clock-fill" {...props}></Icon>
