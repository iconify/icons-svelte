<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hr5hvsl7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hr5hvsl7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ollama-dark" {...props}></Icon>
