<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj6o68bgt.css';
import '../../css/w/wcxlfdb-u.css';
import '../../css/b/bi2qc8bls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cj6o68bgt"/><path class="wcxlfdb-u"/><path class="bi2qc8bls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:compressor-20-bold" {...props}></Icon>
