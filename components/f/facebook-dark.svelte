<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq10kcy8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mq10kcy8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:facebook-dark" {...props}></Icon>
