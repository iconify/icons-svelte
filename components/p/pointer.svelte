<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fek3nqbkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fek3nqbkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:pointer" {...props}></Icon>
