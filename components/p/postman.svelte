<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5pe20bzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m5pe20bzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:postman" {...props}></Icon>
