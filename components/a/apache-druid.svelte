<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewonl9ggj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewonl9ggj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:apache-druid" {...props}></Icon>
