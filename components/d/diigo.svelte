<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow8pqgbao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":264,"height":488};
const content = `<path class="ow8pqgbao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:diigo" {...props}></Icon>
