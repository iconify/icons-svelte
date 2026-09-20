<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfffqbcgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pfffqbcgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:deploydog" {...props}></Icon>
