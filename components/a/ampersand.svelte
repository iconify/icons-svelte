<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpbhpqbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":659,"height":727};
const content = `<path class="tpbhpqbsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:ampersand" {...props}></Icon>
