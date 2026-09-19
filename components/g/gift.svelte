<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qx_it6hge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qx_it6hge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:gift" {...props}></Icon>
