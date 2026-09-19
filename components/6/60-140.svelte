<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq-a3xwaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":528,"height":448};
const content = `<path class="mq-a3xwaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:60-140" {...props}></Icon>
