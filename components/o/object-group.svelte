<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyh-60p9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kyh-60p9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:object-group" {...props}></Icon>
