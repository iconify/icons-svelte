<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evbui5r_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="evbui5r_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:delicious" {...props}></Icon>
