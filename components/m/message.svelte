<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh38uqbex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dh38uqbex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:message" {...props}></Icon>
