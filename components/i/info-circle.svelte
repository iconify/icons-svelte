<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2mwqevna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="k2mwqevna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:info-circle" {...props}></Icon>
