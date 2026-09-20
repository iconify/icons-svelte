<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv28m5ido.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uv28m5ido"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:flohmarkt-dark" {...props}></Icon>
