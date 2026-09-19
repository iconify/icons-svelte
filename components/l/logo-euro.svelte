<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpk8ljbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fpk8ljbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-euro" {...props}></Icon>
