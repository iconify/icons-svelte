<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9j79ebqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":440};
const content = `<path class="v9j79ebqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:bike" {...props}></Icon>
