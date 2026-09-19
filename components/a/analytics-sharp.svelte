<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1dmnpb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g1dmnpb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:analytics-sharp" {...props}></Icon>
