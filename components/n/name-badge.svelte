<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygbngee6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ygbngee6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:name-badge" {...props}></Icon>
