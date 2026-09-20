<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1d-sni5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="h1d-sni5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:airpods-solid" {...props}></Icon>
