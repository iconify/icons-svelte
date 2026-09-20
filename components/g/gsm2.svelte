<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eygexwqbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="eygexwqbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:gsm2" {...props}></Icon>
