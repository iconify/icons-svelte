<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mstj7kszp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":961};
const content = `<path class="mstj7kszp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:camel" {...props}></Icon>
