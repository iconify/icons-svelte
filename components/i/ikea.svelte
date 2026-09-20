<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqmqz7b3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqmqz7b3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ikea" {...props}></Icon>
