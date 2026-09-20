<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuo4hqbuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iuo4hqbuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:librechat-light" {...props}></Icon>
