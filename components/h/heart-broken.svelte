<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-rpnk9-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="k-rpnk9-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:heart-broken" {...props}></Icon>
