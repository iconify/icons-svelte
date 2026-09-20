<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us2nzrqbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="us2nzrqbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dumb-genius-dark" {...props}></Icon>
