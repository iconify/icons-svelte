<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjm6t_b4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":274};
const content = `<path clip-rule="evenodd" class="tjm6t_b4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:datadog" {...props}></Icon>
