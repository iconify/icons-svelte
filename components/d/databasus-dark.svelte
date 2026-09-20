<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itizmxbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="itizmxbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:databasus-dark" {...props}></Icon>
