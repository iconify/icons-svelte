<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iptj19dee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iptj19dee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:person-merpeople" {...props}></Icon>
