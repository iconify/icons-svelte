<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-cmzcb8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="q-cmzcb8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:beauty-salon" {...props}></Icon>
