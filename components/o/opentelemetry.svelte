<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gd5rgu-5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gd5rgu-5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:opentelemetry" {...props}></Icon>
