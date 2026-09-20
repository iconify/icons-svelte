<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5xb6efyw.css';
import '../../css/h/hxjqz7bii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v5xb6efyw"/><path class="hxjqz7bii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bandcamp" {...props}></Icon>
