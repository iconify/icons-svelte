<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpzqbecjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bpzqbecjl primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-right-duotone" {...props}></Icon>
