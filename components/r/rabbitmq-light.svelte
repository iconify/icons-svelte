<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7l31kb1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o7l31kb1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rabbitmq-light" {...props}></Icon>
