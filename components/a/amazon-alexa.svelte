<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp3swkbiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hp3swkbiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:amazon-alexa" {...props}></Icon>
