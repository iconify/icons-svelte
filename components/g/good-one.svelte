<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nea67geye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nea67geye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:good-one" {...props}></Icon>
