<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q36h1kl5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q36h1kl5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:peer-calls-dark" {...props}></Icon>
