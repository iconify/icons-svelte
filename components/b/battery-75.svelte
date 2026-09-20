<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q689h4b1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="q689h4b1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:battery-75" {...props}></Icon>
