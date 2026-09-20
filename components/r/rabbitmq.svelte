<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1fhrac-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1fhrac-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:rabbitmq" {...props}></Icon>
